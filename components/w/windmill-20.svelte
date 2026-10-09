<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukjsobcvo.css';
import '../../css/v/vss9bg_wd.css';
import '../../css/c/cndhhqb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukjsobcvo"/><path class="vss9bg_wd"/><path class="cndhhqb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:windmill-20" {...props}></Icon>
