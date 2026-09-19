<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-m60o1rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q-m60o1rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:star-fill" {...props}></Icon>
