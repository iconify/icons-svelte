<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_ddctbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_ddctbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-collaborate-group-remix" {...props}></Icon>
