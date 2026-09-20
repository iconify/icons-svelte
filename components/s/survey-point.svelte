<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzjpt7h1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mzjpt7h1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:survey-point" {...props}></Icon>
