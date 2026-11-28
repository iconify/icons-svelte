<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-he_3dyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-he_3dyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-arrow-right" {...props}></Icon>
