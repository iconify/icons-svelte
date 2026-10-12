<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo8-8l0ji.css';
import '../../css/n/nd0nkt-ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lo8-8l0ji"/><path class="nd0nkt-ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:set-square-20-bold" {...props}></Icon>
