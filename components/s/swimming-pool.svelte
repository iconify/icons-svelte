<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmbsf60om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jmbsf60om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:swimming-pool" {...props}></Icon>
