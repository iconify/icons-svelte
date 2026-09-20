<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs-tdbc1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xs-tdbc1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:verified-filled" {...props}></Icon>
