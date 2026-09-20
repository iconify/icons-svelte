<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe5b5hnci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe5b5hnci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vultr" {...props}></Icon>
