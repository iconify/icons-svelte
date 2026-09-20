<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlv7qya0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlv7qya0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-top-fill" {...props}></Icon>
