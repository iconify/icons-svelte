<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_p0phbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_p0phbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:watch-square-disable-remix" {...props}></Icon>
