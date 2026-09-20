<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj_14pclx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qj_14pclx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-bad-fill" {...props}></Icon>
