<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky62jqufl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky62jqufl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-unite-alt" {...props}></Icon>
