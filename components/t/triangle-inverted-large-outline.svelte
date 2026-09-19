<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trnm7w1kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="trnm7w1kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:triangle-inverted-large-outline" {...props}></Icon>
