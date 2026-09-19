<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to2lt32jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="to2lt32jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vih" {...props}></Icon>
