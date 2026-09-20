<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6ii2cbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6ii2cbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:suitcase2" {...props}></Icon>
