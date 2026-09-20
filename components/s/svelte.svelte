<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8t4edcla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8t4edcla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:svelte" {...props}></Icon>
