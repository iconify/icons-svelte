<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf821objv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf821objv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sign-right" {...props}></Icon>
