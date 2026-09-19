<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzjyi_b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qzjyi_b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:trophy" {...props}></Icon>
