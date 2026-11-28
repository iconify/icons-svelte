<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqjrbf98n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqjrbf98n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:store-check" {...props}></Icon>
