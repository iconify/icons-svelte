<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/c/c2npje.css';
import '../../css/n/nhjobb.css';
import '../../css/t/ttyihg.css';
import '../../css/s/so-from-70.css';
import '../../css/d/d-4c0-hc.css';
import '../../css/d/d-i58k3z.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c c2npje"/><path class="nhjobb"/><path class="a0m25c ttyihg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:tablet-screenshot" {...props}></Icon>
