<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq1tombzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gq1tombzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:triangle-inverted-medium" {...props}></Icon>
