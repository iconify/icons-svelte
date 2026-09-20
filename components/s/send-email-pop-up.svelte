<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz18cqbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz18cqbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:send-email-pop-up" {...props}></Icon>
