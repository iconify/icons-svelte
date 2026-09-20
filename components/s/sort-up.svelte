<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4h4c4zzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4h4c4zzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-up" {...props}></Icon>
