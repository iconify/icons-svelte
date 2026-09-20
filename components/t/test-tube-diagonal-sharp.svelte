<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3jqvyryi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3jqvyryi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:test-tube-diagonal-sharp" {...props}></Icon>
