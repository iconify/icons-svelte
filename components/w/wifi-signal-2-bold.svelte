<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9cv03zhd.css';
import '../../css/y/ywys0bcog.css';
import '../../css/m/ma0-lhh3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9cv03zhd"/><path class="ywys0bcog"/><path class="ma0-lhh3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wifi-signal-2-bold" {...props}></Icon>
