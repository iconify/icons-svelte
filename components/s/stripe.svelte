<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxn2zjbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="lxn2zjbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:stripe" {...props}></Icon>
