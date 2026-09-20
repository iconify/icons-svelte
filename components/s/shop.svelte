<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7z48943u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7z48943u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:shop" {...props}></Icon>
