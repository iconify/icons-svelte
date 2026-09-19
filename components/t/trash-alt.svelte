<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_kz3cc2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q_kz3cc2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:trash-alt" {...props}></Icon>
