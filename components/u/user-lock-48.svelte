<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmbcisb5f.css';
import '../../css/k/ktb8eibqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kmbcisb5f"/><path class="ktb8eibqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-lock-48" {...props}></Icon>
