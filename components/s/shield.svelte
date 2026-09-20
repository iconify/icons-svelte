<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkqz2lbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kkqz2lbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield" {...props}></Icon>
