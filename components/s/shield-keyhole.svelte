<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs_bt_-6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xs_bt_-6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:shield-keyhole" {...props}></Icon>
