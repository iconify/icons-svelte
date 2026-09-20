<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw1iverzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw1iverzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shock-absorber" {...props}></Icon>
