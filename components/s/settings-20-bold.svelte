<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijh-5sqyq.css';
import '../../css/o/okm62lwzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ijh-5sqyq"/><path class="okm62lwzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:settings-20-bold" {...props}></Icon>
