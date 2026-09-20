<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm3y845ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jm3y845ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-tip-fill" {...props}></Icon>
