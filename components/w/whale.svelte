<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl-uq5pno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl-uq5pno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:whale" {...props}></Icon>
