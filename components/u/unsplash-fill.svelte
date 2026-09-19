<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhi-8zbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhi-8zbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:unsplash-fill" {...props}></Icon>
