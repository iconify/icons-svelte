<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os23_sbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os23_sbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sizing" {...props}></Icon>
