<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl3noccnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sl3noccnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-minus-filled" {...props}></Icon>
