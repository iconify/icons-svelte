<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf2jfbb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf2jfbb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zincsearch" {...props}></Icon>
