<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prs0t9bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prs0t9bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:windy" {...props}></Icon>
