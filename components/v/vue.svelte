<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njca8dbxl.css';
import '../../css/a/as0inn2-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njca8dbxl"/><path class="as0inn2-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vue" {...props}></Icon>
