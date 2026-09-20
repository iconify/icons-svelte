<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/s/s2s9oh.css';
import '../../css/u/ubssyn.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c s2s9oh"/><path class="a0m25c ubssyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:taco" {...props}></Icon>
