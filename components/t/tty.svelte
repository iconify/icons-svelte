<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmytx5v5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="kmytx5v5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tty" {...props}></Icon>
