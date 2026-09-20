<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg2589wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lsg2589wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:world-alt-fill" {...props}></Icon>
