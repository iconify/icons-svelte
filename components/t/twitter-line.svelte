<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpz6nsfpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpz6nsfpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:twitter-line" {...props}></Icon>
