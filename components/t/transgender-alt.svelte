<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukw6yum5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="ukw6yum5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:transgender-alt" {...props}></Icon>
