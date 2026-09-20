<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbwbytb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="rbwbytb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:sun-f" {...props}></Icon>
