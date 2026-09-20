<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjwzk4bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qjwzk4bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-user-bold" {...props}></Icon>
