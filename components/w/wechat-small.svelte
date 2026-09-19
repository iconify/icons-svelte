<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amy0yq-al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="amy0yq-al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wechat-small" {...props}></Icon>
