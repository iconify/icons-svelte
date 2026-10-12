<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i60v-5ifv.css';
import '../../css/y/y8or9ebdh.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i60v-5ifv"/><path class="y8or9ebdh"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:router-x-48-bold" {...props}></Icon>
