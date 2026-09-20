<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqzu86jcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqzu86jcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shopping-bag-sharp" {...props}></Icon>
