<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukv352b1i.css';
import '../../css/n/n1m7q-3fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukv352b1i"/><path class="n1m7q-3fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:upload-24" {...props}></Icon>
