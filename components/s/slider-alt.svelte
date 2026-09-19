<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpe1df_uk.css';
import '../../css/q/q94q71bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpe1df_uk"/><path class="q94q71bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:slider-alt" {...props}></Icon>
