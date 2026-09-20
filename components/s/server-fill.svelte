<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b66k_dq-g.css';
import '../../css/k/k-jty3jzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b66k_dq-g"/><path clip-rule="evenodd" class="k-jty3jzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:server-fill" {...props}></Icon>
