<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwc7t8bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwc7t8bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:shirt-flat" {...props}></Icon>
