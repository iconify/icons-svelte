<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3jr0zbzo.css';
import '../../css/s/sdwec7b_p.css';
import '../../css/f/f674p_02h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3jr0zbzo"/><path class="sdwec7b_p"/><path class="f674p_02h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-alt" {...props}></Icon>
