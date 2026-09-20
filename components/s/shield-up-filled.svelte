<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjkpwbc6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qjkpwbc6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-up-filled" {...props}></Icon>
