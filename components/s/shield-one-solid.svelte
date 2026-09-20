<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k06pmzdrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k06pmzdrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-one-solid" {...props}></Icon>
