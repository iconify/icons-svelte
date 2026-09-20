<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b73v1dh2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b73v1dh2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-single-neutral-male-remix" {...props}></Icon>
