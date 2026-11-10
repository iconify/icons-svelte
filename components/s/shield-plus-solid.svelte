<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma8js3b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ma8js3b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-plus-solid" {...props}></Icon>
