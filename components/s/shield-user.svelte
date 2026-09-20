<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knevdtbla.css';
import '../../css/x/xvp3v8omv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knevdtbla"/><path class="xvp3v8omv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shield-user" {...props}></Icon>
