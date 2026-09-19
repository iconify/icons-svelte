<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5qiuibuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k5qiuibuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:thumbs-up" {...props}></Icon>
