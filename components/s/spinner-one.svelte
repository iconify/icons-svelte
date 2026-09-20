<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcamdxkrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcamdxkrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:spinner-one" {...props}></Icon>
