<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssjp49gnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ssjp49gnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:spouting-whale" {...props}></Icon>
