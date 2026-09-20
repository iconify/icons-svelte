<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idqb9kbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idqb9kbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:stock" {...props}></Icon>
