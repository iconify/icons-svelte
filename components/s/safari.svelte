<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaa9xgbbh.css';
import '../../css/q/q_br50bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jaa9xgbbh"/><path class="q_br50bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:safari" {...props}></Icon>
