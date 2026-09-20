<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8xzfol_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8xzfol_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-facebook" {...props}></Icon>
