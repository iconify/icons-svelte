<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma6hw-ozv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma6hw-ozv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trending-up-down-fill" {...props}></Icon>
