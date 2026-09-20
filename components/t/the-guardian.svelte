<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed943sbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed943sbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:the-guardian" {...props}></Icon>
