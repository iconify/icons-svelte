<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/ymv2uu5iv.css';
import '../../css/a/aj9cdbcjg.css';
import '../../css/a/a5ps3ubbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymv2uu5iv"/><path class="aj9cdbcjg"/><path class="a5ps3ubbp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:star-award-01" {...props}></Icon>
