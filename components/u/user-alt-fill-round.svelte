<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riazaaboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riazaaboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-alt-fill-round" {...props}></Icon>
