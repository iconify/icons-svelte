<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw245nb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jw245nb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:switch-account-1-bold" {...props}></Icon>
