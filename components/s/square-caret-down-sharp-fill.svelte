<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjquvbcqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjquvbcqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-caret-down-sharp-fill" {...props}></Icon>
