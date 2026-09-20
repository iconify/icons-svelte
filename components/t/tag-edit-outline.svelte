<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_qgbl9st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_qgbl9st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-edit-outline" {...props}></Icon>
