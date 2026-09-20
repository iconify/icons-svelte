<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs41k2b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs41k2b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-single-neutral-female-remix" {...props}></Icon>
