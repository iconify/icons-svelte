<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/webyvtyva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="webyvtyva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:three-finger-02" {...props}></Icon>
