<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-wru_mwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-wru_mwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-alert-fill" {...props}></Icon>
