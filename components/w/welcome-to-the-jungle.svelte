<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9zetgbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9zetgbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:welcome-to-the-jungle" {...props}></Icon>
