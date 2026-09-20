<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imv8u3_9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imv8u3_9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transaction-yen" {...props}></Icon>
