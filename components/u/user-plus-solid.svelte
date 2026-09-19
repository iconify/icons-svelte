<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os6dgybfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os6dgybfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:user-plus-solid" {...props}></Icon>
