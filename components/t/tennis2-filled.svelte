<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tby6k6z2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tby6k6z2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tennis2-filled" {...props}></Icon>
