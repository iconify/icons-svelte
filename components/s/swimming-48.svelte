<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbfu520ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tbfu520ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:swimming-48" {...props}></Icon>
