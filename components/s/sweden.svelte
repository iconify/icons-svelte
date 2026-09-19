<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfkrmrb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfkrmrb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:sweden" {...props}></Icon>
