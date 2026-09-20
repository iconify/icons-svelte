<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtly26bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtly26bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-alpha-up" {...props}></Icon>
