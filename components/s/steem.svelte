<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovnmu6bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ovnmu6bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:steem" {...props}></Icon>
