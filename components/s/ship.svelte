<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccyq5bk1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccyq5bk1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:ship" {...props}></Icon>
