<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5e1o8u-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5e1o8u-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shirt-sharp-fill" {...props}></Icon>
