<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we6n59b6n.css';
import '../../css/n/nmu_9kcuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="we6n59b6n"/><path class="nmu_9kcuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:text-size" {...props}></Icon>
