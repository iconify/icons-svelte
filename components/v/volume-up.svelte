<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il2cuacvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-3};
const content = `<path class="il2cuacvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:volume-up" {...props}></Icon>
