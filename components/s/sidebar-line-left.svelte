<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhcb065st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhcb065st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:sidebar-line-left" {...props}></Icon>
