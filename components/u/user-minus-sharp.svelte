<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxosvw3ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxosvw3ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:user-minus-sharp" {...props}></Icon>
