<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwzwdmpba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iwzwdmpba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tower-defensive" {...props}></Icon>
