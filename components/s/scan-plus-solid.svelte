<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkxesj40f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkxesj40f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-plus-solid" {...props}></Icon>
