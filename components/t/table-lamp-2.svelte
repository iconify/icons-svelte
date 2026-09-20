<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzxkhmb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzxkhmb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:table-lamp-2" {...props}></Icon>
