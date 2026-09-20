<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic_lku5dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic_lku5dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zx" {...props}></Icon>
