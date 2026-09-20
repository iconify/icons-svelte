<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c37kw4biu.css';
import '../../css/n/nr6yb3djc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c37kw4biu"/><path class="nr6yb3djc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:server-add-bold" {...props}></Icon>
