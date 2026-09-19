<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_447hrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3_447hrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:scooter-filled" {...props}></Icon>
