<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7r2ndbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7r2ndbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:school-lock-alt-outline" {...props}></Icon>
