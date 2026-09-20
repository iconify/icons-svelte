<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcjq9ynkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcjq9ynkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:times-solid" {...props}></Icon>
