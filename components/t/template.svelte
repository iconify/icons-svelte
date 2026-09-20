<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaw9vtb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaw9vtb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:template" {...props}></Icon>
