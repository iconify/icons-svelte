<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-pw7k70z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-pw7k70z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sparkle-sharp-fill" {...props}></Icon>
