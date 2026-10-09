<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tupyodbki.css';
import '../../css/k/k19v9_bwo.css';
import '../../css/c/cizg-mbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tupyodbki"/><path class="k19v9_bwo"/><path class="cizg-mbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-pump-48" {...props}></Icon>
