<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab1eokbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab1eokbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-down-sharp-fill" {...props}></Icon>
