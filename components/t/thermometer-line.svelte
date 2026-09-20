<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyci4acry.css';
import '../../css/j/jy7_ogj-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyci4acry"/><path class="jy7_ogj-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thermometer-line" {...props}></Icon>
