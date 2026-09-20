<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c977libih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c977libih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:uservoice" {...props}></Icon>
