<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnqnhcbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnqnhcbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:triangle-left-fill" {...props}></Icon>
