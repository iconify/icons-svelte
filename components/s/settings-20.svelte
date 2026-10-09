<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uckaycc9t.css';
import '../../css/t/t170-qrdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uckaycc9t"/><path class="t170-qrdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:settings-20" {...props}></Icon>
