<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuhezrb5q.css';
import '../../css/r/rjngqpptk.css';
import '../../css/p/p5qbymbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuhezrb5q"/><circle class="rjngqpptk"/><path class="p5qbymbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:service-plan" {...props}></Icon>
