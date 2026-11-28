<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz8hg6bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz8hg6bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-square-check" {...props}></Icon>
